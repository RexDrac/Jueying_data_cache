gating-layer-size: [32, 32]
critic-activation-fn: ['relu', 'relu', 'None']
HLC-frequency: 25
loss-output-bound-coeff: 0.0
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
LLC-frequency: 500
actor-layer-size: [256, 256]
epoch-step-num: 5000000
max-step-num: 2500000000
joint-interpolation: True
record-start-size: 10000.0
dsr-gait-period: 0.6
categorical-distribution: {'v_min': -10, 'v_max': 250, 'n_atoms': 51}
imitation-weight: 0.5
max-path-step: 5000
replay-start-size: 10000
actor-activation-fn: ['relu', 'relu', 'None']
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
max-path-num: 20
expert-index: None
critic-lr: 0.0003
epoch-num: 500
render-eval: False
train-step-num: 1
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
filter-torque: False
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
prioritized-exp-replay: True
loss-output-diff-coeff: 0
expert-num: 4
gating-activation-fn: ['relu', 'relu', 'None']
reward-scale: 0.1
tau: 0.001
batch-size: 128
test-num: 4
max-test-time: 10
state-dim: 25
actor-weight-decay: 1e-06
task-weight: 0.5
critic-layer-size: [256, 256]
action-dim: 12
bullet-default-PD: False
env-id: HumanoidBalanceFilter-v0
gating-index: None
filter-action: True
Physics-frequency: 1000
interpolation: False
replay-buffer-size: 1000000
max-episode-num: 5000000
loss-entropy-coeff: 0.0
actor-lr: 0.0003
actor-l2-reg: 0.0003
total-step-num: 2500000000
replay-ratio: 1
rollout-step-num: 1
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
gamma: 0.955
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
critic-weight-decay: 1e-06
max-train-time: 10
squash-action: True
loss-output-smooth-coeff: 1.0
dsr-gait-freq: 1.667
n-step: 1
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
critic-l2-reg: 0.0003
