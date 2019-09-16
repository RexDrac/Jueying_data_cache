max-train-time: 10
replay-buffer-size: 1000000
batch-size: 128
n-step: 1
expert-index: None
rollout-step-num: 1
categorical-distribution: {'v_min': -10, 'v_max': 250, 'n_atoms': 51}
critic-layer-size: [256, 256]
joint-interpolation: True
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-lr: 0.0003
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
loss-output-smooth-coeff: 1.0
gamma: 0.955
epoch-num: 500
epoch-step-num: 5000000
actor-layer-size: [256, 256]
test-num: 4
max-step-num: 2500000000
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
expert-num: 4
state-dim: 25
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
max-episode-num: 5000000
prioritized-exp-replay: True
replay-ratio: 1
gating-activation-fn: ['relu', 'relu', 'None']
actor-l2-reg: 0.0003
filter-action: True
critic-lr: 0.0003
squash-action: True
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
imitation-weight: 0.5
critic-weight-decay: 1e-06
interpolation: False
filter-torque: False
actor-activation-fn: ['relu', 'relu', 'None']
reward-scale: 0.1
critic-l2-reg: 0.0003
critic-activation-fn: ['relu', 'relu', 'None']
action-dim: 12
max-test-time: 10
max-path-step: 5000
Physics-frequency: 1000
LLC-frequency: 500
loss-entropy-coeff: 0.0
dsr-gait-freq: 1.667
bullet-default-PD: False
gating-layer-size: [32, 32]
record-start-size: 10000.0
actor-weight-decay: 1e-06
max-path-num: 20
task-weight: 0.5
env-id: HumanoidBalanceFilter-v0
train-step-num: 1
dsr-gait-period: 0.6
render-eval: False
gating-index: None
HLC-frequency: 25
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
tau: 0.001
replay-start-size: 10000
loss-output-diff-coeff: 0
total-step-num: 2500000000
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
loss-output-bound-coeff: 0.0
