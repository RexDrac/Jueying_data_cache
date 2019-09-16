action-dim: 12
dsr-gait-period: 0.6
expert-index: None
max-path-num: 20
loss-output-smooth-coeff: 1.0
squash-action: True
critic-lr: 0.0003
gamma: 0.955
replay-start-size: 10000
filter-action: True
gating-layer-size: [32, 32]
gating-activation-fn: ['relu', 'relu', 'None']
epoch-step-num: 5000000
critic-layer-size: [256, 256]
gating-index: None
env-id: HumanoidBalanceFilter-v0
max-episode-num: 5000000
reward-scale: 0.1
replay-ratio: 1
max-path-step: 5000
critic-l2-reg: 0.0003
train-step-num: 1
interpolation: False
max-step-num: 2500000000
actor-layer-size: [256, 256]
expert-num: 4
render-eval: False
actor-activation-fn: ['relu', 'relu', 'None']
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
max-train-time: 10
actor-lr: 0.0003
state-dim: 25
epoch-num: 500
actor-l2-reg: 0.0003
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
record-start-size: 10000.0
loss-output-bound-coeff: 0.0
dsr-gait-freq: 1.667
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
actor-weight-decay: 1e-06
loss-output-diff-coeff: 0
test-num: 4
bullet-default-PD: False
Physics-frequency: 1000
imitation-weight: 0.5
joint-interpolation: True
max-test-time: 10
LLC-frequency: 500
n-step: 1
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
prioritized-exp-replay: True
filter-torque: False
critic-weight-decay: 1e-06
tau: 0.001
rollout-step-num: 1
replay-buffer-size: 1000000
critic-activation-fn: ['relu', 'relu', 'None']
task-weight: 0.5
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
categorical-distribution: {'v_max': 250, 'v_min': -10, 'n_atoms': 51}
total-step-num: 2500000000
loss-entropy-coeff: 0.0
batch-size: 128
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
HLC-frequency: 25
